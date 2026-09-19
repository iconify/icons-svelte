<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek0dmobsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1536};
const content = `<path class="ek0dmobsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hashtag" {...props}></Icon>
