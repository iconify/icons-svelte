<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpk_m-oiv.css';
import '../../css/q/qhbzephbs.css';
import '../../css/y/ydp0b-b3w.css';
import '../../css/c/cu0gh7bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpk_m-oiv"/><path class="qhbzephbs"/><path class="ydp0b-b3w"/><path class="cu0gh7bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:full-light" {...props}></Icon>
