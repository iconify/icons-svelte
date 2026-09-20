<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hga3uqbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hga3uqbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-slash" {...props}></Icon>
