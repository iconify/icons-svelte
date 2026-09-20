<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ga9tbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3ga9tbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bed-single-sharp" {...props}></Icon>
