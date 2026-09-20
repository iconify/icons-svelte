<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t52p9_bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t52p9_bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:basket-alt-light" {...props}></Icon>
