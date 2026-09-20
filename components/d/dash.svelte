<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqfvs8b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kqfvs8b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:dash" {...props}></Icon>
