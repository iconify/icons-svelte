<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a8mf9bbkj.css';
import '../../css/o/o9hzagbky.css';
import '../../css/c/c_n8ujbwe.css';
import '../../css/u/udzdqjn5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="a8mf9bbkj"/><path class="o9hzagbky"/><path class="c_n8ujbwe"/><path class="udzdqjn5g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:group-add" {...props}></Icon>
