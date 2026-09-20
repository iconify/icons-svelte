<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq9pkcaia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq9pkcaia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-left-circle" {...props}></Icon>
