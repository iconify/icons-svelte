<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6oc-wo6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6oc-wo6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-heart" {...props}></Icon>
