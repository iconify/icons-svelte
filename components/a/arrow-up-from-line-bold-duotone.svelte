<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqha-5bom.css';
import '../../css/j/jsdqiibqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqha-5bom"/><path class="jsdqiibqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-from-line-bold-duotone" {...props}></Icon>
