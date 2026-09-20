<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge7wz3biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ge7wz3biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:copy" {...props}></Icon>
