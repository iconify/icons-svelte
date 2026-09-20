<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ce2fvzi3c.css';
import '../../css/v/v0jecto8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ce2fvzi3c"/><path class="v0jecto8p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:blank-calendar-flat" {...props}></Icon>
