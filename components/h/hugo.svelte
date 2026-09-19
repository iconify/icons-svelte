<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb3m88byk.css';
import '../../css/b/ba1fozbwm.css';
import '../../css/v/v3or5zb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kb3m88byk"/><path class="ba1fozbwm"/><path class="v3or5zb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:hugo" {...props}></Icon>
