<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z53litb-a.css';
import '../../css/b/bp0qj4bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z53litb-a"/><path class="bp0qj4bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-task" {...props}></Icon>
