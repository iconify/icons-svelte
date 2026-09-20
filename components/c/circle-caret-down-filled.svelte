<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga72qv3aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga72qv3aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-caret-down-filled" {...props}></Icon>
