<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee4nf81dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee4nf81dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:pencil" {...props}></Icon>
