<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr-sxhb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kr-sxhb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:food-spotting-logo-1-solid" {...props}></Icon>
