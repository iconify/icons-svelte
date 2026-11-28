<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm85orbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm85orbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-code-solid" {...props}></Icon>
