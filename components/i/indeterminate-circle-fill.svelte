<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di-drkbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di-drkbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:indeterminate-circle-fill" {...props}></Icon>
