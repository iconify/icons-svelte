<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntopc1bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntopc1bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:inner-shadow-top-left-filled" {...props}></Icon>
