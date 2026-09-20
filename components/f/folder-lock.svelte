<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqotro3ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iqotro3ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-lock" {...props}></Icon>
