<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr5u3zcnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yr5u3zcnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-right-solid" {...props}></Icon>
