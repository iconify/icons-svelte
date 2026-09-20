<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exs-ljbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="exs-ljbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:backpack" {...props}></Icon>
