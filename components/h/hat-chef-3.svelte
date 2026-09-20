<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndhjbdc0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndhjbdc0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hat-chef-3" {...props}></Icon>
