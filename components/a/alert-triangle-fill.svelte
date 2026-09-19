<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbs_-r7it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbs_-r7it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:alert-triangle-fill" {...props}></Icon>
