<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njmoeib8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njmoeib8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-left-top" {...props}></Icon>
