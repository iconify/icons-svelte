<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nijwh4svl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nijwh4svl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-koala-gloss" {...props}></Icon>
