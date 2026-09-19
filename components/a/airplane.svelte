<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y7xmh9s8j.css';
import '../../css/f/f2drsob5a.css';
import '../../css/o/onf5sqgqe.css';
import '../../css/f/fnize7bxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="y7xmh9s8j"/><path class="f2drsob5a"/><path class="onf5sqgqe"/><path class="fnize7bxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:airplane" {...props}></Icon>
