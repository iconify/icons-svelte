<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr-t0ebcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr-t0ebcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:gift" {...props}></Icon>
