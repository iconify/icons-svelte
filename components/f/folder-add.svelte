<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3p33cche.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3p33cche"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-add" {...props}></Icon>
