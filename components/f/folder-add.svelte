<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol2x7rbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ol2x7rbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:folder-add" {...props}></Icon>
