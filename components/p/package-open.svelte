<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fji14kbbh.css';
import '../../css/b/b144n1btn.css';
import '../../css/f/f_ksnwbtv.css';
import '../../css/p/pgw3asb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fji14kbbh wm-a"/><path class="b144n1btn wm-k"/><path class="f_ksnwbtv wm-k"/><path class="pgw3asb-i wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:package-open" {...props}></Icon>
