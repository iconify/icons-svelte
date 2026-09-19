<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwzc_4j9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xwzc_4j9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cog-6-tooth" {...props}></Icon>
