<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecisew_dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecisew_dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-remove-thin" {...props}></Icon>
