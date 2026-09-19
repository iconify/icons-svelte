<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uywerpb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uywerpb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-up-outline" {...props}></Icon>
