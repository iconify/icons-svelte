<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vatjnl35z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vatjnl35z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:list-checks-solid" {...props}></Icon>
