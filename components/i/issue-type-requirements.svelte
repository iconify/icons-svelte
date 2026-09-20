<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfv3ot-fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nfv3ot-fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:issue-type-requirements" {...props}></Icon>
