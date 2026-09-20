<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obh2e_72q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="obh2e_72q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pcgamingwiki" {...props}></Icon>
