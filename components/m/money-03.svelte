<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a_9gjeb9i.css';
import '../../css/d/dzqmh_brh.css';
import '../../css/g/gi37vtblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a_9gjeb9i"/><path class="dzqmh_brh"/><path class="gi37vtblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:money-03" {...props}></Icon>
