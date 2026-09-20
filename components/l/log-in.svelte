<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-uzbcchb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-3};
const content = `<path class="a-uzbcchb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:log-in" {...props}></Icon>
