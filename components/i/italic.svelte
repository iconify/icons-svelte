<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srt553b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="srt553b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:italic" {...props}></Icon>
