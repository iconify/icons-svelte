<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edxk8nbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edxk8nbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:link-2" {...props}></Icon>
