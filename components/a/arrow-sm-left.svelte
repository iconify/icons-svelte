<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilwl7-91o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilwl7-91o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-sm-left" {...props}></Icon>
