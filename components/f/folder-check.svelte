<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pur09rb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pur09rb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-check" {...props}></Icon>
