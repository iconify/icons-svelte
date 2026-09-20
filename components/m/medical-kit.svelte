<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/okvu0ui1q.css';
import '../../css/e/e8e9occnp.css';
import '../../css/m/mdux50sgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="okvu0ui1q"/><path clip-rule="evenodd" class="e8e9occnp"/><path clip-rule="evenodd" class="mdux50sgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:medical-kit" {...props}></Icon>
