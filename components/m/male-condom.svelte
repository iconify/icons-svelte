<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcqu-00yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dcqu-00yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:male-condom" {...props}></Icon>
