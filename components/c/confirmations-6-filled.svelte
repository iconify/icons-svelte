<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8xadmzxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8xadmzxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-6-filled" {...props}></Icon>
