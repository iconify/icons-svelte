<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvvpbts5o.css';
import '../../css/t/txrxn8dlv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="cvvpbts5o"/><path class="txrxn8dlv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nixos-wordmark" {...props}></Icon>
