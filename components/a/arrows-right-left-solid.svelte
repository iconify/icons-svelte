<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwhv55k-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwhv55k-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-right-left-solid" {...props}></Icon>
