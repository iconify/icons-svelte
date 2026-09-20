<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/h/hzcqba.css';
import '../../css/s/sbei0c.css';
import '../../css/g/gvulyl.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c hzcqba"/><path class="a0m25c sbei0c"/><path class="a0m25c gvulyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-align-center" {...props}></Icon>
