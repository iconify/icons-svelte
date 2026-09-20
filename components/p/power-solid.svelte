<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5y3vccqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="s5y3vccqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:power-solid" {...props}></Icon>
