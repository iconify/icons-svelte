<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykwqglbwb.css';
import '../../css/p/p18co30jw.css';
import '../../css/c/cglx9k6ox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ykwqglbwb"/><path class="p18co30jw"/><path class="cglx9k6ox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-input-20" {...props}></Icon>
