<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miazw5f2j.css';
import '../../css/n/n1xy6nh9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miazw5f2j"/><circle class="n1xy6nh9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-compass" {...props}></Icon>
