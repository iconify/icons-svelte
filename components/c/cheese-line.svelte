<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihpfuxbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihpfuxbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:cheese-line" {...props}></Icon>
