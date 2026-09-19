<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_57cqbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a_57cqbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:html5" {...props}></Icon>
