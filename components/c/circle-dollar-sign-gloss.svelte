<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enj0h4zby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enj0h4zby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-dollar-sign-gloss" {...props}></Icon>
