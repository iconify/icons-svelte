<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5bp7pmdg.css';
import '../../css/z/z5-9hkvso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l5bp7pmdg"/><path class="z5-9hkvso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:diskette" {...props}></Icon>
