<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkqs-fbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkqs-fbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:note-edit" {...props}></Icon>
