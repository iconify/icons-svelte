<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acao7vxke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acao7vxke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-code" {...props}></Icon>
