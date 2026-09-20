<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb3ybbs_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sb3ybbs_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:credit-card" {...props}></Icon>
