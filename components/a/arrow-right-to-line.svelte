<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bobh2gb4b.css';
import '../../css/z/z7ntss-zu.css';
import '../../css/s/swgz-mbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bobh2gb4b"/><path class="z7ntss-zu"/><path class="swgz-mbqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-right-to-line" {...props}></Icon>
