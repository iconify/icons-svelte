<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv2_brboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rv2_brboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:doc-code" {...props}></Icon>
