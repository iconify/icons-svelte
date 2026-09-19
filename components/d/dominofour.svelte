<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq6gfzbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":960};
const content = `<path class="mq6gfzbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dominofour" {...props}></Icon>
