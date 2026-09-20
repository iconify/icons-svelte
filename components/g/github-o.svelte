<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh74e8blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jh74e8blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:github-o" {...props}></Icon>
