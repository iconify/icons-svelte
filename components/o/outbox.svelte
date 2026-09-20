<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shbp87bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="shbp87bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:outbox" {...props}></Icon>
