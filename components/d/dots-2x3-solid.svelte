<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcw80rb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcw80rb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x3-solid" {...props}></Icon>
