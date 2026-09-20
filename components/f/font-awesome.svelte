<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgkes3bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgkes3bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:font-awesome" {...props}></Icon>
