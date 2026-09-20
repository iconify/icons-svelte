<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5a7rwu8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5a7rwu8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote" {...props}></Icon>
