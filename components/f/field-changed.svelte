<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v44l5dlia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v44l5dlia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:field-changed" {...props}></Icon>
