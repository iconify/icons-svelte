<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi1xs8bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi1xs8bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:flower" {...props}></Icon>
