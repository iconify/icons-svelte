<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcitvccga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcitvccga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ftc" {...props}></Icon>
