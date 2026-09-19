<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o22u0m-kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o22u0m-kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:arrow-right" {...props}></Icon>
