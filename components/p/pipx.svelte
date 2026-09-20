<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsbyav3kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsbyav3kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pipx" {...props}></Icon>
