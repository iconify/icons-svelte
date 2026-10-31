<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/r/rm-j65frv.css';
import '../../css/t/txfh-5blw.css';
import '../../css/t/tdfzwrb2o.css';
import '../../css/v/vzoejcc3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="rm-j65frv wm-shadow"/><path class="txfh-5blw wm-shadow"/><path class="tdfzwrb2o"/><path class="vzoejcc3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:play" {...props}></Icon>
