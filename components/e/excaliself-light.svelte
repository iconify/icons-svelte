<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzr8gqboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fzr8gqboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:excaliself-light" {...props}></Icon>
