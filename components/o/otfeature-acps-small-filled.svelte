<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cumjaub7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cumjaub7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-acps-small-filled" {...props}></Icon>
