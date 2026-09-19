<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqa3tkb1n.css';
import '../../css/i/i3fv60jeg.css';
import '../../css/x/xxaa87b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="sqa3tkb1n"><path class="i3fv60jeg"/><path class="xxaa87b_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:calendar-xmark-solid" {...props}></Icon>
