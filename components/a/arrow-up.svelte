<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/komf3mb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="komf3mb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-up" {...props}></Icon>
