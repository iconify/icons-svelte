<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f35yy7v4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f35yy7v4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ghost" {...props}></Icon>
