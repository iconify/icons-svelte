<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx_vtdb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cx_vtdb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fx-tag-solid" {...props}></Icon>
