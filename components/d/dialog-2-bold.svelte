<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dff8bp7ci.css';
import '../../css/g/gpwxw0bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dff8bp7ci"/><path class="gpwxw0bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dialog-2-bold" {...props}></Icon>
