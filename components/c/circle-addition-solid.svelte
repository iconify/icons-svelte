<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blr1bqy5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="blr1bqy5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:circle-addition-solid" {...props}></Icon>
