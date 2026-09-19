<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qei0usz3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qei0usz3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:favoritefolder" {...props}></Icon>
