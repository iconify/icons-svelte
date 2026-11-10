<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/www7zt58m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="www7zt58m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cloud-exclamation-solid" {...props}></Icon>
