<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plek-ib1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plek-ib1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:git-commit-check" {...props}></Icon>
