<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o79d83b5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o79d83b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:home-circle" {...props}></Icon>
