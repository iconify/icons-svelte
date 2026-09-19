<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utg4a_brp.css';
import '../../css/o/o104vdwci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="utg4a_brp"/><path class="o104vdwci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-subtract" {...props}></Icon>
