<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zdw9dcb7o.css';
import '../../css/m/mfefy2b5h.css';
import '../../css/a/avnz0dbim.css';
import '../../css/a/aia7l3btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="ft5dv1b6b"><rect class="zdw9dcb7o"/><path clip-rule="evenodd" class="mfefy2b5h"/><path clip-rule="evenodd" class="avnz0dbim"/><path clip-rule="evenodd" class="aia7l3btd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="skill-icons:activitypub-dark" {...props}></Icon>
