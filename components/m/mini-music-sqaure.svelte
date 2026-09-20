<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/ii3b9xbkx.css';
import '../../css/t/t8r6agbqp.css';
import '../../css/b/bn9scm_6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ii3b9xbkx"/><path class="t8r6agbqp"/><path class="bn9scm_6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mini-music-sqaure" {...props}></Icon>
