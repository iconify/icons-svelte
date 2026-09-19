<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2nqf8t8e.css';
import '../../css/v/vqb--ibgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n2nqf8t8e"/><path class="vqb--ibgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-closed-captioning-outline" {...props}></Icon>
