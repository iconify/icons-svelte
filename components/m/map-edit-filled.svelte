<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezedetb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezedetb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-edit-filled" {...props}></Icon>
