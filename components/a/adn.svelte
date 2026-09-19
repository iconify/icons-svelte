<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnpf4yb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tnpf4yb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:adn" {...props}></Icon>
