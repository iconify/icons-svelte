<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a39x7accg.css';
import '../../css/w/w3pk7wb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a39x7accg"/><path class="w3pk7wb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-narrow-wide" {...props}></Icon>
