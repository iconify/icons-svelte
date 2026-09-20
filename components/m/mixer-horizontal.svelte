<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lme84c1eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lme84c1eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:mixer-horizontal" {...props}></Icon>
