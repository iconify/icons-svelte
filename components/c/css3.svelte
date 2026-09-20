<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we5ld5buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="we5ld5buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:css3" {...props}></Icon>
