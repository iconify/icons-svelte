<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvsz9dblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jvsz9dblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:api-outlined" {...props}></Icon>
