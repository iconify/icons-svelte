<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep3yudvpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep3yudvpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:graduation-cap-check" {...props}></Icon>
