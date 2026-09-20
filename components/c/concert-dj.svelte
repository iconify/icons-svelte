<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/rwelgybmu.css';
import '../../css/v/v-i0on6ks.css';
import '../../css/a/ac61dbckf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rwelgybmu"/><path class="v-i0on6ks"/><path class="ac61dbckf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:concert-dj" {...props}></Icon>
