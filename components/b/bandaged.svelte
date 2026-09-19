<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4-48zo7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v4-48zo7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bandaged" {...props}></Icon>
