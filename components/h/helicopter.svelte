<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flviq_1lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="flviq_1lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:helicopter" {...props}></Icon>
