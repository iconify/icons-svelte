<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w9jvul8en.css';
import '../../css/l/l6a3mob9c.css';
import '../../css/d/d2vzwr-fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="w9jvul8en"/><path class="l6a3mob9c"/><path class="d2vzwr-fl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:book-check-duotone" {...props}></Icon>
