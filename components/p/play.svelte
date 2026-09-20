<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2vrhrbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="j2vrhrbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:play" {...props}></Icon>
