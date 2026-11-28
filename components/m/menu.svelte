<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un_p-dbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un_p-dbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:menu" {...props}></Icon>
