<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu5-twbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu5-twbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:database-plus-corner-fill-round" {...props}></Icon>
