<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uim7w5btd.css';
import '../../css/q/qvdt6db7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uim7w5btd"/><path class="qvdt6db7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:delivery-drone-bold" {...props}></Icon>
