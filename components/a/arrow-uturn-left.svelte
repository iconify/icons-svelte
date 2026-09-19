<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1zwhfbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n1zwhfbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-uturn-left" {...props}></Icon>
