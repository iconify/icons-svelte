<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1ejkacuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ejkacuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:overline-solid" {...props}></Icon>
