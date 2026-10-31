<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/powor1xqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="powor1xqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:briefcase-fill-round" {...props}></Icon>
