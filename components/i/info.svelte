<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa3v6eogt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa3v6eogt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:info" {...props}></Icon>
