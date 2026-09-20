<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cai9s6bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cai9s6bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-top-plus" {...props}></Icon>
