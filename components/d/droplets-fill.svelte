<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqw673b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqw673b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:droplets-fill" {...props}></Icon>
