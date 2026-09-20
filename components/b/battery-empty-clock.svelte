<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8qahsb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8qahsb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-empty-clock" {...props}></Icon>
