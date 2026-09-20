<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k47yy6bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k47yy6bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:hobby-knife" {...props}></Icon>
