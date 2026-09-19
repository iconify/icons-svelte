<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub88htbiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ub88htbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-1-duotone" {...props}></Icon>
