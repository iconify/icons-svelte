<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_ep6jbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q_ep6jbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:add-shopping-cart" {...props}></Icon>
