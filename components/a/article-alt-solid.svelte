<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbb8jab7i.css';
import '../../css/l/ldmh8bwhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbb8jab7i"/><path class="ldmh8bwhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:article-alt-solid" {...props}></Icon>
