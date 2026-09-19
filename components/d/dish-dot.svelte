<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3s5ci-4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n3s5ci-4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:dish-dot" {...props}></Icon>
