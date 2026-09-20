<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbm4ihbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jbm4ihbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:dots-horizontal" {...props}></Icon>
