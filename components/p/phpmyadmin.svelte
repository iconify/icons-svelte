<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwukq5y6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwukq5y6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:phpmyadmin" {...props}></Icon>
