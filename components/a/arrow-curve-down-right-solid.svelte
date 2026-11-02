<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw6fn5b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dw6fn5b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-down-right-solid" {...props}></Icon>
