<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz9ue_anp.css';
import '../../css/x/xk4xuvuka.css';
import '../../css/x/xfngl4bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz9ue_anp"/><path class="xk4xuvuka"/><path class="xfngl4bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:radio-fill" {...props}></Icon>
