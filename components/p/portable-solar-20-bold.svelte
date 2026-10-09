<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1np659_m.css';
import '../../css/n/n180x7juo.css';
import '../../css/j/jwnchgn9i.css';
import '../../css/j/j8k9-bcng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x1np659_m"/><path class="n180x7juo"/><path class="jwnchgn9i"/><path class="j8k9-bcng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:portable-solar-20-bold" {...props}></Icon>
