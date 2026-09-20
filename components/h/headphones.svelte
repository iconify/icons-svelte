<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogk8lqiry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogk8lqiry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:headphones" {...props}></Icon>
