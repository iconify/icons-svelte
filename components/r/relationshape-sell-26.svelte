<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_dpo2bur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="w_dpo2bur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:relationshape-sell-26" {...props}></Icon>
