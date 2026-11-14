<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbdzc5bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbdzc5bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:power-kw" {...props}></Icon>
