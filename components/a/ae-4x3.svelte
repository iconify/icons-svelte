<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1xzrlbhy.css';
import '../../css/v/v18c9fbau.css';
import '../../css/r/r38kscbse.css';
import '../../css/j/jlqxt-bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="o1xzrlbhy"/><path class="v18c9fbau"/><path class="r38kscbse"/><path class="jlqxt-bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ae-4x3" {...props}></Icon>
