<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2h4v_bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z2h4v_bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:list-checks" {...props}></Icon>
