<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5haedcuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v5haedcuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lilypond" {...props}></Icon>
