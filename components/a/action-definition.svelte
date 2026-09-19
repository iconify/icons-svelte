<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/genudbc9p.css';
import '../../css/a/awir01b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="genudbc9p"/><path class="awir01b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:action-definition" {...props}></Icon>
