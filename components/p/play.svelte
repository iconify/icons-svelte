<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k47n0ww8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k47n0ww8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:play" {...props}></Icon>
