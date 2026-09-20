<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-tunxbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y-tunxbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:new-folder-flat" {...props}></Icon>
