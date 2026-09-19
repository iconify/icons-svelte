<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pco8b6b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="pco8b6b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-text-fill" {...props}></Icon>
