<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sft1b-ftv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sft1b-ftv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:minus" {...props}></Icon>
