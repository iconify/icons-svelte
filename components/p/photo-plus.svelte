<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k099k6bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k099k6bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-plus" {...props}></Icon>
