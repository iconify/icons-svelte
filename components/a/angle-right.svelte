<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f64paxb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f64paxb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:angle-right" {...props}></Icon>
