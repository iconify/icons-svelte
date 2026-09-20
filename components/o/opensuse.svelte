<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mck3r6bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mck3r6bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:opensuse" {...props}></Icon>
