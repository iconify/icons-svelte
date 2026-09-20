<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n4a06hbrq.css';
import '../../css/o/ou9miccvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n4a06hbrq"/><path clip-rule="evenodd" class="ou9miccvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:receipt-add-flat" {...props}></Icon>
