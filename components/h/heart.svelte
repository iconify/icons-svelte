<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thqbk35ga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thqbk35ga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:heart" {...props}></Icon>
