<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_nde8b2s.css';
import '../../css/f/f0yq_obue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_nde8b2s"/><path class="f0yq_obue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:medium-line" {...props}></Icon>
