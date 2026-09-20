<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la6i2f31y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="la6i2f31y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-q-filled" {...props}></Icon>
