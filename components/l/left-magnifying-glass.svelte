<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui_yqjhja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ui_yqjhja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-magnifying-glass" {...props}></Icon>
