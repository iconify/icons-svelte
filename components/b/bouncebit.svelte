<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myew_qb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myew_qb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bouncebit" {...props}></Icon>
