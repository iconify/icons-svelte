<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0o9nrvdg.css';
import '../../css/m/mgns90b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0o9nrvdg"/><path class="mgns90b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:question-mark-bold-duotone" {...props}></Icon>
