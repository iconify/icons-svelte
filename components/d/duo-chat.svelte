<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0l3ckbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c0l3ckbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:duo-chat" {...props}></Icon>
