<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsppapbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsppapbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:annotation" {...props}></Icon>
