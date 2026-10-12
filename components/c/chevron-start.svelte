<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o15fnivdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o15fnivdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:chevron-start" {...props}></Icon>
