<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edu-5ablw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edu-5ablw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-square-info" {...props}></Icon>
