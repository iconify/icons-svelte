<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxm2gnbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxm2gnbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:align-horizontally" {...props}></Icon>
