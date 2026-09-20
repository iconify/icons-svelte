<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn-6ucc2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sn-6ucc2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:minus-small-16" {...props}></Icon>
