<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npa4pmb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npa4pmb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-uturn-down" {...props}></Icon>
