<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlr-l1vuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlr-l1vuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:forbid-2" {...props}></Icon>
