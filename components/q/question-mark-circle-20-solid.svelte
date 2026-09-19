<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-oenbbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w-oenbbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:question-mark-circle-20-solid" {...props}></Icon>
