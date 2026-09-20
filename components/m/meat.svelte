<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9o_mybqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9o_mybqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:meat" {...props}></Icon>
