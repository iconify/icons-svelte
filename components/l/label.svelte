<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rey4ck1nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rey4ck1nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:label" {...props}></Icon>
