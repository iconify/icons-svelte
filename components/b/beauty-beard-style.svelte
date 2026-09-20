<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhl1isbvq.css';
import '../../css/s/sdbok-sel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qhl1isbvq"/><path class="sdbok-sel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:beauty-beard-style" {...props}></Icon>
