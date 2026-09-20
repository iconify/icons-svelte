<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks5i7cc0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks5i7cc0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:food-spotting-logo-2-block" {...props}></Icon>
