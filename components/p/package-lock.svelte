<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on3sloqnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on3sloqnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:package-lock" {...props}></Icon>
