<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzh587b2u.css';
import '../../css/e/e8loo8vjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzh587b2u"/><path class="e8loo8vjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:data-file-bars-edit-bold" {...props}></Icon>
