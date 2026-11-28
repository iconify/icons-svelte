<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp75s3bpj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sggxujywz.css';
import '../../css/t/tod053bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp75s3bpj secondary"/><g class="dt0cm9dhy primary"><path class="sggxujywz"/><path class="tod053bcv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pennant-duo" {...props}></Icon>
