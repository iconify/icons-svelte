<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayspz-bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ayspz-bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:brave" {...props}></Icon>
