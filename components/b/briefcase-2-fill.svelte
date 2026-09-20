<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia_s7c2er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia_s7c2er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:briefcase-2-fill" {...props}></Icon>
