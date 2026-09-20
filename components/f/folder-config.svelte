<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd1yx_bjk.css';
import '../../css/h/htfzp21pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kd1yx_bjk"/><path class="htfzp21pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-config" {...props}></Icon>
