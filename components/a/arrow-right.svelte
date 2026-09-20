<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptjd14b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptjd14b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-right" {...props}></Icon>
