<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj1xpbb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj1xpbb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:hard-drive-fill" {...props}></Icon>
