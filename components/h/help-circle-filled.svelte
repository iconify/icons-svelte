<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b82ebgbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b82ebgbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:help-circle-filled" {...props}></Icon>
