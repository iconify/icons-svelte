<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/c/cqteb8bfj.css';
import '../../css/n/ng8wznwvh.css';
import '../../css/e/egtcd9rqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="cqteb8bfj"/><path class="ng8wznwvh"/><path class="egtcd9rqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:people-rounded" {...props}></Icon>
