<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t24yx0btu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t24yx0btu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:diagram-successor" {...props}></Icon>
