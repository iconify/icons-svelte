<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azj6c3b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azj6c3b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:almalinux" {...props}></Icon>
