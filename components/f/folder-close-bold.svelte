<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3uj0ccyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3uj0ccyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-close-bold" {...props}></Icon>
