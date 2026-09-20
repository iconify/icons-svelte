<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5pn70b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5pn70b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-4-filled" {...props}></Icon>
