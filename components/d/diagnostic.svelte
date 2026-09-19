<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0u3k0lff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g0u3k0lff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:diagnostic" {...props}></Icon>
