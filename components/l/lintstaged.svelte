<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoy029nik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hoy029nik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lintstaged" {...props}></Icon>
