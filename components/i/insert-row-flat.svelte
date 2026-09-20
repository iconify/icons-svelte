<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o4yf71bcc.css';
import '../../css/j/jus-31b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o4yf71bcc"/><path clip-rule="evenodd" class="jus-31b2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:insert-row-flat" {...props}></Icon>
