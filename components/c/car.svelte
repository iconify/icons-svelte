<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2wbqwbqv.css';
import '../../css/t/t4exnpses.css';
import '../../css/j/jzjyesbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2wbqwbqv"/><circle class="t4exnpses"/><circle class="jzjyesbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:car" {...props}></Icon>
