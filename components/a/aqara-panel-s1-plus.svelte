<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-mtglb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-mtglb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-panel-s1-plus" {...props}></Icon>
