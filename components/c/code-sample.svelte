<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-s4vtjqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":14};
const content = `<path class="n-s4vtjqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:code-sample" {...props}></Icon>
