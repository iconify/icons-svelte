<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps9lkiisw.css';
import '../../css/o/oh5vljisv.css';
import '../../css/r/rlcxgmb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ps9lkiisw"/><path class="oh5vljisv"/><path class="rlcxgmb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:content-files-pen" {...props}></Icon>
