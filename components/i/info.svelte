<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qck11v1nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qck11v1nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:info" {...props}></Icon>
