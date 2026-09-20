<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r81h0lbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r81h0lbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:actigraph" {...props}></Icon>
