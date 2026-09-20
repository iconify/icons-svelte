<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3ku02pwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3ku02pwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:erlang" {...props}></Icon>
