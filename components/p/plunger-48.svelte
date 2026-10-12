<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqsth4bzo.css';
import '../../css/l/linospgqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yqsth4bzo"/><path class="linospgqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plunger-48" {...props}></Icon>
