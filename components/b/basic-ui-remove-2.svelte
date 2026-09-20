<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p99d2z6jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p99d2z6jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-remove-2" {...props}></Icon>
