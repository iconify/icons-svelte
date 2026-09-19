<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8yccutwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8yccutwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:puzzle" {...props}></Icon>
