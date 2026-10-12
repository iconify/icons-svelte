<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttki8ltre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttki8ltre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-up-start" {...props}></Icon>
