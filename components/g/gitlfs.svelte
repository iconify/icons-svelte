<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lanrwibss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lanrwibss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gitlfs" {...props}></Icon>
