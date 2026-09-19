<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un5wb_anb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="un5wb_anb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:home-fill" {...props}></Icon>
