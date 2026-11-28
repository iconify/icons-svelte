<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d35cr1bzu.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uuphcfbpa.css';
import '../../css/s/s17gsfb4w.css';
import '../../css/y/y5sn-cbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d35cr1bzu secondary"/><g class="dt0cm9dhy primary"><path class="uuphcfbpa"/><path class="s17gsfb4w"/><path class="y5sn-cbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-copy-duo" {...props}></Icon>
