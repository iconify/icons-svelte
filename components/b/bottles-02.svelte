<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvrrshbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zvrrshbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bottles-02" {...props}></Icon>
