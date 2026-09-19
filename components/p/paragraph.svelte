<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmq_ozbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bmq_ozbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:paragraph" {...props}></Icon>
