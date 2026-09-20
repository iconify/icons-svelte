<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfav8cbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfav8cbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:insert-before" {...props}></Icon>
