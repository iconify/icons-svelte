<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bal_--nnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bal_--nnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gift-fill" {...props}></Icon>
