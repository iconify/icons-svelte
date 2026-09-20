<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib5rjcoyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib5rjcoyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-cancel" {...props}></Icon>
