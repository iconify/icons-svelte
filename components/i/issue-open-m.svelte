<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiy_99hiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xiy_99hiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-open-m" {...props}></Icon>
