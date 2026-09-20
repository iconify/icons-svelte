<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txw99oo3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txw99oo3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:keyboard-fill" {...props}></Icon>
