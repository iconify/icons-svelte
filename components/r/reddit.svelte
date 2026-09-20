<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaq2lhbrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aaq2lhbrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:reddit" {...props}></Icon>
