<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob-dx4zav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob-dx4zav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-right-justified" {...props}></Icon>
