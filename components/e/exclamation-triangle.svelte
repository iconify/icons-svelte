<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwzj-8bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uwzj-8bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:exclamation-triangle" {...props}></Icon>
