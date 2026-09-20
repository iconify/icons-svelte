<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt506yb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt506yb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftteams" {...props}></Icon>
