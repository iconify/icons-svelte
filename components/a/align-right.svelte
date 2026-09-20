<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of83378bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of83378bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:align-right" {...props}></Icon>
