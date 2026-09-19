<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp_jc4bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp_jc4bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-gunnarp-round" {...props}></Icon>
