<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpc_zebhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mpc_zebhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-0-filled" {...props}></Icon>
