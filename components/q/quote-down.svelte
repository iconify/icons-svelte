<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eoyo7mb1z.css';
import '../../css/m/m8fqv418y.css';
import '../../css/e/eoec-qy5u.css';
import '../../css/b/bb82cgb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="eoyo7mb1z"/><path class="m8fqv418y"/><path class="eoec-qy5u"/><path class="bb82cgb6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:quote-down" {...props}></Icon>
