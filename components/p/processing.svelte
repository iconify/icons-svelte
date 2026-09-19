<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hka5spbni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hka5spbni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:processing" {...props}></Icon>
