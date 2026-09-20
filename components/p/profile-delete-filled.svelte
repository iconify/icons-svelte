<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlh38yb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlh38yb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:profile-delete-filled" {...props}></Icon>
