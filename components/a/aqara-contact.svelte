<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-1iavbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-1iavbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-contact" {...props}></Icon>
