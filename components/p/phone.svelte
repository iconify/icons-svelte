<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0b-rzvep.css';
import '../../css/x/xcvr3hbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0b-rzvep"/><path clip-rule="evenodd" class="xcvr3hbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:phone" {...props}></Icon>
