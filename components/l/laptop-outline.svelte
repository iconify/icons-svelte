<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1_uyh1sv.css';
import '../../css/g/g2kbevgvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1_uyh1sv"/><path class="g2kbevgvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-outline" {...props}></Icon>
