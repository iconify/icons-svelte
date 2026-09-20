<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdf1hubnu.css';
import '../../css/f/f69nz6bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kdf1hubnu"/><path clip-rule="evenodd" class="f69nz6bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:push-mgt-filled" {...props}></Icon>
