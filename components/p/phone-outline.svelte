<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s86q4zppz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s86q4zppz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-outline" {...props}></Icon>
