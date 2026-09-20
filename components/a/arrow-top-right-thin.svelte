<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5mq17sgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5mq17sgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-right-thin" {...props}></Icon>
