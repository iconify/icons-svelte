<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm78tdbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm78tdbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:floppy-disk-alt-outline" {...props}></Icon>
