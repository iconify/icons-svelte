<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l6fn0fb1j.css';
import '../../css/v/v9ilm3b2y.css';
import '../../css/w/wq0hmuiej.css';
import '../../css/a/afyu49bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l6fn0fb1j"/><path class="v9ilm3b2y"/><path class="wq0hmuiej"/><path class="afyu49bic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-open-bold" {...props}></Icon>
