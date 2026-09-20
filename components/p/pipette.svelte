<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq0xcgf7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uq0xcgf7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pipette" {...props}></Icon>
