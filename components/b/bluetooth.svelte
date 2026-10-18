<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjc28qb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjc28qb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bluetooth" {...props}></Icon>
