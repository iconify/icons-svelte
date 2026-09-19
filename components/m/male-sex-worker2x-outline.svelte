<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seb9yuicd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="seb9yuicd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:male-sex-worker2x-outline" {...props}></Icon>
