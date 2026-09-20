<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_fb8gn8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a_fb8gn8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:page-setting" {...props}></Icon>
