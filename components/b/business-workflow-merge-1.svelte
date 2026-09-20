<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9s103bcs.css';
import '../../css/n/n3xy1-b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9s103bcs"/><path class="n3xy1-b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:business-workflow-merge-1" {...props}></Icon>
