<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkf9rhutl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hkf9rhutl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bonfire" {...props}></Icon>
