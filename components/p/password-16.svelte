<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtr2w7blj.css';
import '../../css/q/qvhmvvbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mtr2w7blj"/><path clip-rule="evenodd" class="qvhmvvbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:password-16" {...props}></Icon>
