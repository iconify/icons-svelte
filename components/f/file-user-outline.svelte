<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0ogznero.css';
import '../../css/c/cgf21cybt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0ogznero"/><path clip-rule="evenodd" class="cgf21cybt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:file-user-outline" {...props}></Icon>
