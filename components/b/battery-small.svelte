<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q174y-b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="q174y-b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:battery-small" {...props}></Icon>
