<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch5eyfbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch5eyfbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:droplet" {...props}></Icon>
