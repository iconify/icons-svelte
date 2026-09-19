<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7ddr5vqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="g7ddr5vqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-sun-with-rays-small-filled" {...props}></Icon>
