<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np5n44mha.css';
import '../../css/j/j5tmw1bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="np5n44mha"/><path class="j5tmw1bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:purescript" {...props}></Icon>
