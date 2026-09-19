<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kna5n_8so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kna5n_8so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-down-solid" {...props}></Icon>
