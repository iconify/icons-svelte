<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/habq1_bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="habq1_bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:keyboard-fill" {...props}></Icon>
