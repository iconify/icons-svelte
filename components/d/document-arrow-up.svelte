<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twgt3wb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="twgt3wb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:document-arrow-up" {...props}></Icon>
