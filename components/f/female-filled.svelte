<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyu6162qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyu6162qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:female-filled" {...props}></Icon>
