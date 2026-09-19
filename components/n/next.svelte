<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2z8tnr9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="h2z8tnr9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:next" {...props}></Icon>
