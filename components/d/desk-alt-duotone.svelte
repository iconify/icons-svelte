<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/na63v48uc.css';
import '../../css/l/lnd3c0bpx.css';
import '../../css/r/rk3zggbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="na63v48uc"/><path class="lnd3c0bpx"/><path class="rk3zggbju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:desk-alt-duotone" {...props}></Icon>
