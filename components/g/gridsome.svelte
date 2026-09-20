<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t93wronmj.css';
import '../../css/q/qi5qy6i4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="t93wronmj"/><path class="qi5qy6i4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:gridsome" {...props}></Icon>
