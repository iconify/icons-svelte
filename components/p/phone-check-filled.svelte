<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww0w2tjgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww0w2tjgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-check-filled" {...props}></Icon>
