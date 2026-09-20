<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmx4n2bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmx4n2bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pcgamingwiki" {...props}></Icon>
