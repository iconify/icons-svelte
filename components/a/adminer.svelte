<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-kgf2jpm.css';
import '../../css/k/kje3pp6ll.css';
import '../../css/g/gp-ljubwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v-kgf2jpm"/><path class="kje3pp6ll"/><path class="gp-ljubwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:adminer" {...props}></Icon>
