<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-2mv0b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-2mv0b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:prismic" {...props}></Icon>
