<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsy0fcbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsy0fcbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:merge" {...props}></Icon>
