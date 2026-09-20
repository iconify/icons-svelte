<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayicm5b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ayicm5b9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:pencil-2" {...props}></Icon>
