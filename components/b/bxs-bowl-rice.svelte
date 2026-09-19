<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sni227bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sni227bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bowl-rice" {...props}></Icon>
