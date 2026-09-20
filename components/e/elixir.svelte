<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlb081b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlb081b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:elixir" {...props}></Icon>
