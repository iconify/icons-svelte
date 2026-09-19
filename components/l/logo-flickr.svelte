<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjqtc9kwq.css';
import '../../css/n/nod8k7bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="sjqtc9kwq"/><circle class="nod8k7bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-flickr" {...props}></Icon>
