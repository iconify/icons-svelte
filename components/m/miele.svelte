<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm2232bcw.css';
import '../../css/e/ev2u2w4wz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm2232bcw"/><path class="ev2u2w4wz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:miele" {...props}></Icon>
