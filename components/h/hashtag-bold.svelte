<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6zdocb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6zdocb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hashtag-bold" {...props}></Icon>
