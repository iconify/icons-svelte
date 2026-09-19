<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jueq24bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jueq24bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-ttf-small-filled" {...props}></Icon>
