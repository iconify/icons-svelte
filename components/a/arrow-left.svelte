<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3qcs9fwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f3qcs9fwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:arrow-left" {...props}></Icon>
