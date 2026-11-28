<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa53ddb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa53ddb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:office-building" {...props}></Icon>
