<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku_it8bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku_it8bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:email-fill" {...props}></Icon>
