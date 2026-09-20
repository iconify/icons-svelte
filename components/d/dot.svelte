<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gehl5y7ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gehl5y7ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:dot" {...props}></Icon>
