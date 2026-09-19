<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g97jdgv9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g97jdgv9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-bear-right-02" {...props}></Icon>
