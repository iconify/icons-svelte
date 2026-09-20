<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfii3za8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfii3za8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:receipt-sharp-fill" {...props}></Icon>
