<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if49zsb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="if49zsb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:printer" {...props}></Icon>
