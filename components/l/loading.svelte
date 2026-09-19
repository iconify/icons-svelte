<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngowvybto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ngowvybto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:loading" {...props}></Icon>
