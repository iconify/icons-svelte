<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b41cz12cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b41cz12cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:align-left" {...props}></Icon>
