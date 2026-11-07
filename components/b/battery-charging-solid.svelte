<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deahru6an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="deahru6an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:battery-charging-solid" {...props}></Icon>
