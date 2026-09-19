<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9-7c3drh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g9-7c3drh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cursor-arrow-rays" {...props}></Icon>
