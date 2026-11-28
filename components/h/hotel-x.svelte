<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5myccczx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5myccczx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hotel-x" {...props}></Icon>
