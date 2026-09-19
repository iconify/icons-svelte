<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx_wlebbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fx_wlebbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:list-bulleted" {...props}></Icon>
