<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5jbxh.css';
import '../../css/i/iw1iew.css';
import '../../css/r/r1zcwc.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-1.css';
import '../../css/d/d-7xq8qc.css';
import '../../css/d/d-7h3jep.css';
import '../../css/f/fade-qhlvwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5jbxh iw1iew"/><path class="iw1iew r1zcwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:hazard-lights-filled-loop" {...props}></Icon>
