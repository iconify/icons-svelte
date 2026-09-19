<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb2uxglrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb2uxglrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:list-minus" {...props}></Icon>
