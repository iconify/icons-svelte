<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuwpidcny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuwpidcny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:game-jolt" {...props}></Icon>
