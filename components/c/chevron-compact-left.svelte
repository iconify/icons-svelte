<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thankj98l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thankj98l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chevron-compact-left" {...props}></Icon>
