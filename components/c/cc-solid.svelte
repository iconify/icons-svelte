<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2u1s5b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s2u1s5b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cc-solid" {...props}></Icon>
