<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-z9gacxo.css';
import '../../css/i/ifoz_0z4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f-z9gacxo"/><path class="ifoz_0z4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-pencil-brush" {...props}></Icon>
