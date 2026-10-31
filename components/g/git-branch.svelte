<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/g/g1rmqcb6r.css';
import '../../css/o/o-aolgbja.css';
import '../../css/o/om6-cnkwr.css';
import '../../css/i/i6pwf4bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="g1rmqcb6r wm-shadow"/><path class="o-aolgbja"/><path class="om6-cnkwr"/><path class="i6pwf4bws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:git-branch" {...props}></Icon>
