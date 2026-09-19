<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihzocydtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihzocydtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-left" {...props}></Icon>
