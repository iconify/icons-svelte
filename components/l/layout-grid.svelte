<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/h/hful5vo0l.css';
import '../../css/y/yys2mt-hg.css';
import '../../css/b/bgu9jmbze.css';
import '../../css/h/hiyd2bczp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="hful5vo0l"/><path class="yys2mt-hg"/><path class="bgu9jmbze"/><path class="hiyd2bczp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:layout-grid" {...props}></Icon>
