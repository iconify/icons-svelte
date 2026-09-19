<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu6jlzblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wu6jlzblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:hot-water" {...props}></Icon>
