<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q62ov693u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q62ov693u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder-tree" {...props}></Icon>
