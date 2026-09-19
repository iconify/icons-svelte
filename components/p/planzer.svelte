<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfwla4bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfwla4bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:planzer" {...props}></Icon>
