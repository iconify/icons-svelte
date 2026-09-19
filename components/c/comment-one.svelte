<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f66n5zbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f66n5zbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:comment-one" {...props}></Icon>
