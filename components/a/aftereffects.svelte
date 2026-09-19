<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0cuc_bpo.css';
import '../../css/h/h-ofk3o6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n0cuc_bpo"/><path class="h-ofk3o6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:aftereffects" {...props}></Icon>
