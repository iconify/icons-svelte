<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7hym0q5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7hym0q5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-up-box" {...props}></Icon>
