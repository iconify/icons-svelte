<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-6qpzjjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o-6qpzjjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-bar-chart-horizontal-start-fill" {...props}></Icon>
