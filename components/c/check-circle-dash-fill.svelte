<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tww3lhbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tww3lhbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-circle-dash-fill" {...props}></Icon>
