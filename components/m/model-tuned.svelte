<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g15uk9bud.css';
import '../../css/u/u-p-xwb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g15uk9bud"/><path class="u-p-xwb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:model-tuned" {...props}></Icon>
