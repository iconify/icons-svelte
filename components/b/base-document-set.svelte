<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iww3bo28l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iww3bo28l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:base-document-set" {...props}></Icon>
