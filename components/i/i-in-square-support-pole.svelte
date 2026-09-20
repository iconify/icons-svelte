<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu6v7ibol.css';
import '../../css/c/c3skeypjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mu6v7ibol"/><path class="c3skeypjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:i-in-square-support-pole" {...props}></Icon>
