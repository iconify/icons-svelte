<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1ec_1uud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1ec_1uud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paw-round" {...props}></Icon>
