<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmp8azpko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmp8azpko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-smile" {...props}></Icon>
