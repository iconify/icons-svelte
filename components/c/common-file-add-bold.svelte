<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcglrybdp.css';
import '../../css/k/k74euduoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcglrybdp"/><path class="k74euduoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:common-file-add-bold" {...props}></Icon>
