<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag5m9z64z.css';
import '../../css/z/z5kljvobp.css';
import '../../css/i/iv0739boz.css';
import '../../css/y/ynuwzd5vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ag5m9z64z"/><path class="z5kljvobp"/><path class="iv0739boz"/><path class="ynuwzd5vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:filing-cabinet" {...props}></Icon>
