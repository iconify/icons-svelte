<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyy3hyach.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nyy3hyach"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:information-circle" {...props}></Icon>
