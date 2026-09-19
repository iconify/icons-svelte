<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx1pw_-qf.css';
import '../../css/g/g5xqtsbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="SVGmEns5cJB" class="nx1pw_-qf"/></defs><use href="#SVGmEns5cJB"/><use href="#SVGmEns5cJB"/><path class="g5xqtsbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:new-tab" {...props}></Icon>
