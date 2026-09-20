<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-ac16mjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ac16mjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:escalator-down-fill" {...props}></Icon>
