<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyv8m4uoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyv8m4uoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail" {...props}></Icon>
