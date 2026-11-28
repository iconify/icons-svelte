<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z83ayhbhi.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/t/tyobncbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z83ayhbhi"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="tyobncbux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-eighth-duo" {...props}></Icon>
