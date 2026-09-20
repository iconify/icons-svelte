<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s36q-6b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s36q-6b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:expensify" {...props}></Icon>
