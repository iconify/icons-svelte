<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfqbr3bdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfqbr3bdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-x-sharp" {...props}></Icon>
