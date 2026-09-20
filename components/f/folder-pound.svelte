<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5oa-eblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5oa-eblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-pound" {...props}></Icon>
