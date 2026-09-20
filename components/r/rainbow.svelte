<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oty3txbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oty3txbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:rainbow" {...props}></Icon>
