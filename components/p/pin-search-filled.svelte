<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygkepvbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ygkepvbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin-search-filled" {...props}></Icon>
