<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgch26bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dgch26bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bell-snooze-solid" {...props}></Icon>
