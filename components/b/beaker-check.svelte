<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okd59c11y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okd59c11y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:beaker-check" {...props}></Icon>
