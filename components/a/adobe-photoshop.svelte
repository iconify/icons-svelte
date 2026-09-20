<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fonifab6t.css';
import '../../css/q/qpkq3pbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<rect class="fonifab6t"/><path class="qpkq3pbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:adobe-photoshop" {...props}></Icon>
