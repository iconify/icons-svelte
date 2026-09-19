<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng8fflbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="ng8fflbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brailleu" {...props}></Icon>
