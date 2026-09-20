<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsebfebzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lsebfebzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:clipboard" {...props}></Icon>
