<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez4qt3bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez4qt3bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-1-light" {...props}></Icon>
