<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oahi-jwnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oahi-jwnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:computer-chip-32-bold" {...props}></Icon>
