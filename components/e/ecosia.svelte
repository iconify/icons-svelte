<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5ci-16ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5ci-16ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ecosia" {...props}></Icon>
