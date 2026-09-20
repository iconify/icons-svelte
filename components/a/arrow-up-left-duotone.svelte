<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhyjf-b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhyjf-b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-left-duotone" {...props}></Icon>
