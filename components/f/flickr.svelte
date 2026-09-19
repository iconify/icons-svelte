<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjfy5bbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="qjfy5bbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:flickr" {...props}></Icon>
