<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/h_l78yaxm.css';
import '../../css/p/pvy_1nbjw.css';
import '../../css/u/ugb540alo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><ellipse class="h_l78yaxm"/><path class="pvy_1nbjw"/><path class="ugb540alo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:database-zap" {...props}></Icon>
