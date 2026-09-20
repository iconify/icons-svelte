<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqy-zd.css';
import '../../css/x/x9nrmw.css';
import '../../css/y/ydovum.css';
import '../../css/d/dmm0ha.css';
import '../../css/v/vpa1li.css';
import '../../css/s/so-from-60.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqy-zd"/><path class="x9nrmw ydovum"/><path class="dmm0ha ydovum"/><path class="vpa1li ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:iconify1" {...props}></Icon>
