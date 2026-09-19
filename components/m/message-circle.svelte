<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulz3miwzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulz3miwzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:message-circle" {...props}></Icon>
