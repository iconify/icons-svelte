<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqq8rqbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqq8rqbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:electricity-filled" {...props}></Icon>
