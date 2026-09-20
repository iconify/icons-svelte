<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iba-o7bgl.css';
import '../../css/f/fzrqn6dxq.css';
import '../../css/k/kuz0qbccj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="iba-o7bgl"/><path class="fzrqn6dxq"/><path class="kuz0qbccj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="unjs:node-fetch-native" {...props}></Icon>
