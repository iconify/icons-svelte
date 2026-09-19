<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv6u3ea9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv6u3ea9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:building-office-2" {...props}></Icon>
