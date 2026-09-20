<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1n6o1qej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1n6o1qej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:incognito-mode" {...props}></Icon>
