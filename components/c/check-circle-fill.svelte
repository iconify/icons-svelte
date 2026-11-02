<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia090xb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia090xb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-circle-fill" {...props}></Icon>
