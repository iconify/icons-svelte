<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4c5vcbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":77,"height":654};
const content = `<path class="c4c5vcbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:period" {...props}></Icon>
