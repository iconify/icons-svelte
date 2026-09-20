<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apju6mbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="apju6mbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:paperclip" {...props}></Icon>
