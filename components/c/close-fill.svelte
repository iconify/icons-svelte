<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjkg-qtlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jjkg-qtlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:close-fill" {...props}></Icon>
