<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o43on_1lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="o43on_1lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:angle" {...props}></Icon>
