<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beziji2lr.css';
import '../../css/a/a274jortb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beziji2lr"/><path class="a274jortb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:fluid" {...props}></Icon>
