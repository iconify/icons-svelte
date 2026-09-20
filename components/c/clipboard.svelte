<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct5_d9bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct5_d9bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:clipboard" {...props}></Icon>
