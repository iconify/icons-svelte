<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc599u7ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nc599u7ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:layout" {...props}></Icon>
