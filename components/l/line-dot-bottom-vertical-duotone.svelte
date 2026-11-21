<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o5l2aiban.css';
import '../../css/a/aasift6kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o5l2aiban"/><path class="aasift6kd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:line-dot-bottom-vertical-duotone" {...props}></Icon>
