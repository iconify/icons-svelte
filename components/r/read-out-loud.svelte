<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw7kt4bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qw7kt4bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:read-out-loud" {...props}></Icon>
