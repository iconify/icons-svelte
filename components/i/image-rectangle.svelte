<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bigwdsbpk.css';
import '../../css/y/yjtz3ka2h.css';
import '../../css/h/h5bp3ks6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bigwdsbpk"/><path class="yjtz3ka2h"/><path class="h5bp3ks6u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:image-rectangle" {...props}></Icon>
