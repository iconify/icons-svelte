<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltt-bqb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltt-bqb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:laravel-solid" {...props}></Icon>
