<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8h5xmbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m8h5xmbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:arrange-send-backward" {...props}></Icon>
