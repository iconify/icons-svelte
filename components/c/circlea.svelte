<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kihavfb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kihavfb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlea" {...props}></Icon>
