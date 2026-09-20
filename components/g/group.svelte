<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gl9hcebao.css';
import '../../css/j/j2vkrw2rq.css';
import '../../css/g/gv6tiib9t.css';
import '../../css/x/x7jcu8bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="gl9hcebao"/><path class="j2vkrw2rq"/><path class="gv6tiib9t"/><path class="x7jcu8bha"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:group" {...props}></Icon>
