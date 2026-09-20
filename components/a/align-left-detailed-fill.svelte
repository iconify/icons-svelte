<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x37ks3dss.css';
import '../../css/i/i8iix-ktc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x37ks3dss"/><path clip-rule="evenodd" class="i8iix-ktc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-left-detailed-fill" {...props}></Icon>
