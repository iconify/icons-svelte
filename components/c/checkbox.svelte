<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efz_1fkfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="efz_1fkfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:checkbox" {...props}></Icon>
