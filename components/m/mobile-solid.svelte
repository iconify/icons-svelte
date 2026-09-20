<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeqbun34w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="jeqbun34w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mobile-solid" {...props}></Icon>
