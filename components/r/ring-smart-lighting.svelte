<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er6g1acjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er6g1acjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ring-smart-lighting" {...props}></Icon>
