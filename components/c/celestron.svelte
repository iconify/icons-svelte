<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fin3fg2wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fin3fg2wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:celestron" {...props}></Icon>
