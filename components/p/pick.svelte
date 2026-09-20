<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1jwqxbwc.css';
import '../../css/o/onmnzxzya.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/h/hqn-ljbgu.css';
import '../../css/s/s8lqfob4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="q1jwqxbwc"/><path class="onmnzxzya"/><g class="jn8qy4bru"><path class="hqn-ljbgu"/><path class="s8lqfob4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pick" {...props}></Icon>
