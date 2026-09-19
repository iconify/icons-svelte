<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx6oijbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tx6oijbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:item-usage" {...props}></Icon>
