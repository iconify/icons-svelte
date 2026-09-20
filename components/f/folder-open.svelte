<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbrjnsjii.css';
import '../../css/x/xatleqcvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbrjnsjii"/><path class="xatleqcvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:folder-open" {...props}></Icon>
