<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guiwvcb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guiwvcb9b primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-6-duotone" {...props}></Icon>
