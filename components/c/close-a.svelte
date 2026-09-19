<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgci3mbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgci3mbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:close-a" {...props}></Icon>
