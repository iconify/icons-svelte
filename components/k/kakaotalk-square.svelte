<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgak4ob9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="cgak4ob9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:kakaotalk-square" {...props}></Icon>
