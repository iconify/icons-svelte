<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ep0lbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m9ep0lbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:logo-abletonlink" {...props}></Icon>
