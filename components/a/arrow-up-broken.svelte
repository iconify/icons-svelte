<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9nvxccti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9nvxccti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-broken" {...props}></Icon>
