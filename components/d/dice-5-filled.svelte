<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waergt57a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waergt57a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dice-5-filled" {...props}></Icon>
