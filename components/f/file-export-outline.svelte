<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es8hrw68o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es8hrw68o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-export-outline" {...props}></Icon>
