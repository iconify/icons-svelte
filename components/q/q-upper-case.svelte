<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9f6c35gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="k9f6c35gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:q-upper-case" {...props}></Icon>
