<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcmkkhb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcmkkhb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:insert-after" {...props}></Icon>
