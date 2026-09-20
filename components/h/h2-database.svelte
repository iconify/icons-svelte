<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml7wh4fzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ml7wh4fzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:h2-database" {...props}></Icon>
