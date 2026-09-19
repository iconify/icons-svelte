<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqbn4acve.css';
import '../../css/p/pjyeu65td.css';
import '../../css/h/hcj6o-bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqbn4acve"/><circle class="pjyeu65td"/><circle class="hcj6o-bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:face-mask" {...props}></Icon>
