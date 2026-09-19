<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu2_-nbje.css';
import '../../css/e/e6t7vc15w.css';
import '../../css/s/sfus55blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nu2_-nbje"/><path class="e6t7vc15w"/><path class="sfus55blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:location-company" {...props}></Icon>
