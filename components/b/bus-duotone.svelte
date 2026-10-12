<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/osormye2v.css';
import '../../css/x/xo23v9bqf.css';
import '../../css/j/j9wettb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="osormye2v"/><path class="xo23v9bqf"/><path class="j9wettb5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bus-duotone" {...props}></Icon>
