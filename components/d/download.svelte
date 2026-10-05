<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/i/i6psyz68x.css';
import '../../css/o/o6ain5brh.css';
import '../../css/p/p_u131ihg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="i6psyz68x"/><path class="o6ain5brh"/><path class="p_u131ihg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:download" {...props}></Icon>
