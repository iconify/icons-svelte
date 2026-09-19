<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quy73rill.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quy73rill"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-dollar" {...props}></Icon>
