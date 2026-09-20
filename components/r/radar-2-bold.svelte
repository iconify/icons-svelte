<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrb3zebso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrb3zebso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-2-bold" {...props}></Icon>
