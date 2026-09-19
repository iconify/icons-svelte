<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g41r0y9di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g41r0y9di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:chevron-left-med" {...props}></Icon>
