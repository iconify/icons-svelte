<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_38gnb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_38gnb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:arrow-up-down" {...props}></Icon>
