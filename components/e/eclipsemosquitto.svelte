<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkfl6o0qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkfl6o0qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:eclipsemosquitto" {...props}></Icon>
