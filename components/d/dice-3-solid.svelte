<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wablnj0pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wablnj0pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-3-solid" {...props}></Icon>
