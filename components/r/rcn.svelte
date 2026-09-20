<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqy8xebjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqy8xebjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rcn" {...props}></Icon>
