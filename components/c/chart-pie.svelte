<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egtvu8r9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egtvu8r9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-pie" {...props}></Icon>
