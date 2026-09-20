<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzyyi-baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzyyi-baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:burncloud" {...props}></Icon>
