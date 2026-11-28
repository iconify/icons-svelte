<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmv3p70cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmv3p70cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-right-solid" {...props}></Icon>
