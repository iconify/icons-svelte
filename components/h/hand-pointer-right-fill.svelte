<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf7-bcbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uf7-bcbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-pointer-right-fill" {...props}></Icon>
