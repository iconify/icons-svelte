<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkea-w76j.css';
import '../../css/u/u52trxfes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkea-w76j"/><path class="u52trxfes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:contacts-filled" {...props}></Icon>
