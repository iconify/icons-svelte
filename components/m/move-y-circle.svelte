<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mn4bp7bsf.css';
import '../../css/z/zhk99f-bo.css';
import '../../css/y/ya22fsvpd.css';
import '../../css/c/c1xb2abra.css';
import '../../css/x/xrgx2dblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="mn4bp7bsf"/><path class="zhk99f-bo"/><path class="ya22fsvpd"/><path class="c1xb2abra"/><path class="xrgx2dblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:move-y-circle" {...props}></Icon>
