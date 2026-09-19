<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc_tpzbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc_tpzbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bacon-alt" {...props}></Icon>
