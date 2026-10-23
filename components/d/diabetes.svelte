<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/je1cs0byc.css';
import '../../css/y/y9flf7vox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="je1cs0byc"/><path class="y9flf7vox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:diabetes" {...props}></Icon>
