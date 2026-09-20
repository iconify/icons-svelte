<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag6dbfbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ag6dbfbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:hydrogen-bold" {...props}></Icon>
