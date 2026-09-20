<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-el6m66m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l-el6m66m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:control-start" {...props}></Icon>
