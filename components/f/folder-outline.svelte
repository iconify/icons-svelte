<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui6f1wb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ui6f1wb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:folder-outline" {...props}></Icon>
