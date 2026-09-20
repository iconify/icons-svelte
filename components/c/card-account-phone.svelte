<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxogo41px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxogo41px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-account-phone" {...props}></Icon>
