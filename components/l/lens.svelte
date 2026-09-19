<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp3n9jxlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qp3n9jxlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lens" {...props}></Icon>
