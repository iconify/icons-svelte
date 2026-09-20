<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo49cibud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo49cibud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hourglass" {...props}></Icon>
