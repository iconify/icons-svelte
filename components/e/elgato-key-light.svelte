<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdzz6xdbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdzz6xdbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:elgato-key-light" {...props}></Icon>
