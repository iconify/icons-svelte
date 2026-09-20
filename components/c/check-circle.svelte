<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td6n-mrnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td6n-mrnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:check-circle" {...props}></Icon>
