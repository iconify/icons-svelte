<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udtx5jbky.css';
import '../../css/e/elmdxu0vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="udtx5jbky"/><path class="elmdxu0vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:phone-outgoing-filled" {...props}></Icon>
