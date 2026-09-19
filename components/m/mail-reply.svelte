<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b33o66b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="b33o66b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mail-reply" {...props}></Icon>
