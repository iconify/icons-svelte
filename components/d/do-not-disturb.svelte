<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/d/dbgvcxwad.css';
import '../../css/o/o-w-gbbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="dbgvcxwad"/><path class="o-w-gbbnp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:do-not-disturb" {...props}></Icon>
