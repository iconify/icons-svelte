<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl4-xoo_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fl4-xoo_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:car-solid" {...props}></Icon>
