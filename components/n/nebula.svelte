<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu6kj3bqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu6kj3bqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nebula" {...props}></Icon>
