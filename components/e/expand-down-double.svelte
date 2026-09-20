<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljkx69bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljkx69bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-down-double" {...props}></Icon>
