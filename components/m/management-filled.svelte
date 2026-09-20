<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob_vnvbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ob_vnvbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:management-filled" {...props}></Icon>
