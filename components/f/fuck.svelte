<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px4ty5bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":472};
const content = `<path class="px4ty5bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:fuck" {...props}></Icon>
