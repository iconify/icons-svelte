<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmp10-bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmp10-bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:euro" {...props}></Icon>
