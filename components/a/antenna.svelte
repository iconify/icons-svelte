<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/ta-b9kowj.css';
import '../../css/y/y6m4-subp.css';
import '../../css/l/ltxc5lndl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ta-b9kowj"/><path class="y6m4-subp"/><path class="ltxc5lndl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:antenna" {...props}></Icon>
