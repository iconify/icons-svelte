<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px0eocvtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="px0eocvtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-sun-with-rays-small" {...props}></Icon>
