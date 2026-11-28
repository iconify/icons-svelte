<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9wb71y_y.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mnkxd3b9o.css';
import '../../css/a/a_d29mp8e.css';
import '../../css/r/rxfs97xjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9wb71y_y secondary"/><g class="dt0cm9dhy primary"><path class="mnkxd3b9o"/><path class="a_d29mp8e"/><path class="rxfs97xjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pancakes-duo" {...props}></Icon>
