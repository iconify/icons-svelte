<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd2ryx8bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd2ryx8bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-css" {...props}></Icon>
