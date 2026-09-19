<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky3unnbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":342,"height":512};
const content = `<path class="ky3unnbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:coq" {...props}></Icon>
