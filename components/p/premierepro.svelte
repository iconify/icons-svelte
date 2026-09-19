<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_om5egbx.css';
import '../../css/a/aucylab8w.css';
import '../../css/p/pimz7_f2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v_om5egbx"/><path class="aucylab8w"/><path class="pimz7_f2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:premierepro" {...props}></Icon>
