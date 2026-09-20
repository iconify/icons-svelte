<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox-rx1bbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ox-rx1bbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-nursery" {...props}></Icon>
