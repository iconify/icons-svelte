<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u49fm9evw.css';
import '../../css/f/fzn8913pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="u49fm9evw"/><path class="fzn8913pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:ansys" {...props}></Icon>
