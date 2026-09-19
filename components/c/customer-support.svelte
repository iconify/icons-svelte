<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/obblj4bwn.css';
import '../../css/d/d-9yqyjnd.css';
import '../../css/o/ogj5jkb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="obblj4bwn"/><path class="d-9yqyjnd"/><path class="ogj5jkb9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:customer-support" {...props}></Icon>
