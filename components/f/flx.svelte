<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awmhj_7ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="awmhj_7ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:flx" {...props}></Icon>
