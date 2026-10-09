<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afkvrrboz.css';
import '../../css/q/qekqfrbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="afkvrrboz"/><path class="qekqfrbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-left-up-20-bold" {...props}></Icon>
