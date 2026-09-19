<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqm51mwuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jqm51mwuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-3" {...props}></Icon>
