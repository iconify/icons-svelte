<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i6uzpybyf.css';
import '../../css/p/phm_mqkqd.css';
import '../../css/w/w6pvigl7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6uzpybyf"/><path class="phm_mqkqd"/><path class="w6pvigl7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:radio-receiver-duotone" {...props}></Icon>
