<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl68r0buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zl68r0buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:cog-flat" {...props}></Icon>
