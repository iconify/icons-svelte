<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7ceq3bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n7ceq3bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:restore" {...props}></Icon>
