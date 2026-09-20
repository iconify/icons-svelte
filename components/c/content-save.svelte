<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1m8t89qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o1m8t89qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-save" {...props}></Icon>
