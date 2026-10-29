<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imt3fu8pc.css';
import '../../css/g/g9wjd3b3c.css';
import '../../css/o/oqnjuob9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imt3fu8pc"/><path class="g9wjd3b3c"/><path class="oqnjuob9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:more-horizontal" {...props}></Icon>
