<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_t1md8jp.css';
import '../../css/i/ihw0bkbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i_t1md8jp"/><path class="ihw0bkbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cpp" {...props}></Icon>
