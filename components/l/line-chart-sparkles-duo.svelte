<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7lniib-c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nhobn03np.css';
import '../../css/o/oc7p48bdb.css';
import '../../css/o/oi3kjkbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7lniib-c secondary"/><g class="dt0cm9dhy primary"><path class="nhobn03np"/><path class="oc7p48bdb"/><path class="oi3kjkbsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:line-chart-sparkles-duo" {...props}></Icon>
