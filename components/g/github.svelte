<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx3cpnbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":760,"height":800};
const content = `<path class="cx3cpnbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:github" {...props}></Icon>
