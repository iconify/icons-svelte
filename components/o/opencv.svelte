<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxz6et8is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxz6et8is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:opencv" {...props}></Icon>
