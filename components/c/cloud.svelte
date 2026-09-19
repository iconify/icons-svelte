<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/toc71bc9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="toc71bc9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cloud" {...props}></Icon>
