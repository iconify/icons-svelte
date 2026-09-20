<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k16uybc-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k16uybc-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-fill" {...props}></Icon>
