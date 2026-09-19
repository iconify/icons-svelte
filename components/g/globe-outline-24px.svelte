<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opuvz3osb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="opuvz3osb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:globe-outline-24px" {...props}></Icon>
