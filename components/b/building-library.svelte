<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk25et9co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk25et9co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:building-library" {...props}></Icon>
