<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljx1946ba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljx1946ba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-open-fill" {...props}></Icon>
