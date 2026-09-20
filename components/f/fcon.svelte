<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfr41bc0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfr41bc0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fcon" {...props}></Icon>
