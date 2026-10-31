<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/y/ybis5fb1d.css';
import '../../css/r/rn913dbor.css';
import '../../css/a/ay8cv7rvn.css';
import '../../css/d/dx8clgbog.css';
import '../../css/h/h2yet72fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="ybis5fb1d"/><path class="rn913dbor wm-shine"/><path class="ay8cv7rvn wm-k"/><path class="dx8clgbog wm-a"/><path class="h2yet72fy wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:database-backup" {...props}></Icon>
