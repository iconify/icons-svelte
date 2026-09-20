<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9r8s4rsw.css';
import '../../css/h/h6klkqbsh.css';
import '../../css/q/qf19skb9v.css';
import '../../css/e/eux5nikfz.css';
import '../../css/i/ihq6w6b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d9r8s4rsw"/><path class="h6klkqbsh"/><circle class="qf19skb9v"/><path class="eux5nikfz"/><path class="ihq6w6b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:figma-light" {...props}></Icon>
