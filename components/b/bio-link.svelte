<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsa0o9kyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsa0o9kyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bio-link" {...props}></Icon>
