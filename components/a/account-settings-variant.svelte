<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmkw9x26d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmkw9x26d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-settings-variant" {...props}></Icon>
