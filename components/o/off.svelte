<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq-5i-b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nq-5i-b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:off" {...props}></Icon>
