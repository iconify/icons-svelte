<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlfg3onlw.css';
import '../../css/x/xa153ngzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlfg3onlw"/><circle class="xa153ngzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:question" {...props}></Icon>
