<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyult47py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyult47py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-up-on-square-stack" {...props}></Icon>
