<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn1pczm7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bn1pczm7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-top-right-on-square" {...props}></Icon>
