<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u95fdqnwb.css';
import '../../css/k/ku7fde-py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u95fdqnwb"/><path clip-rule="evenodd" class="ku7fde-py"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:padlock-shield-flat" {...props}></Icon>
