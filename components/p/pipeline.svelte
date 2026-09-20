<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icsgmp8vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="icsgmp8vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:pipeline" {...props}></Icon>
