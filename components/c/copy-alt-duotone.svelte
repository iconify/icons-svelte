<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wlj7muv1i.css';
import '../../css/o/ob0ilvbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wlj7muv1i"/><path class="ob0ilvbgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:copy-alt-duotone" {...props}></Icon>
