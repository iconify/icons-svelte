<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbc_il0ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbc_il0ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:diamond-plus" {...props}></Icon>
