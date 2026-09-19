<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eok69sb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eok69sb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:layout-align-bottom" {...props}></Icon>
