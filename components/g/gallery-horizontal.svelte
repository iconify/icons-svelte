<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ea3o1dbkq.css';
import '../../css/b/b6vsz4bbf.css';
import '../../css/s/so2kmrb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ea3o1dbkq"/><path class="b6vsz4bbf"/><path class="so2kmrb9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gallery-horizontal" {...props}></Icon>
