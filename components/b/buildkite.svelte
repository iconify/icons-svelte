<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdaiqpzaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdaiqpzaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:buildkite" {...props}></Icon>
