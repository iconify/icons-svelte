<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eskjnab0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eskjnab0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:inner-shadow-bottom-filled" {...props}></Icon>
