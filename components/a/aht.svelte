<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw74mcvdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tw74mcvdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aht" {...props}></Icon>
