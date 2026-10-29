<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fbon0hb5t.css';
import '../../css/g/ggrxnez9p.css';
import '../../css/h/h02h9d79a.css';
import '../../css/g/g3a8c8bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fbon0hb5t"/><path class="ggrxnez9p wm-k"/><path class="h02h9d79a wm-k"/><path class="g3a8c8bfa wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bat-sketch" {...props}></Icon>
