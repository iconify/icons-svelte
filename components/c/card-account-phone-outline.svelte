<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb9u09bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb9u09bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:card-account-phone-outline" {...props}></Icon>
