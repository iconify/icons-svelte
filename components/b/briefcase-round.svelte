<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwtte82_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwtte82_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:briefcase-round" {...props}></Icon>
