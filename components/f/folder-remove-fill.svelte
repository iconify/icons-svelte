<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpczuhuaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rpczuhuaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-remove-fill" {...props}></Icon>
