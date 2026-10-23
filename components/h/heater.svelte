<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esq_-z43o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esq_-z43o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heater" {...props}></Icon>
