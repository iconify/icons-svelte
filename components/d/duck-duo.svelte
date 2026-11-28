<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b23un12lm.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/ciud1kn-e.css';
import '../../css/l/lcrewz3kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b23un12lm secondary"/><g class="dt0cm9dhy primary"><path class="ciud1kn-e"/><path class="lcrewz3kz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:duck-duo" {...props}></Icon>
