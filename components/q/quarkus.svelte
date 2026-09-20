<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3lpwpz8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3lpwpz8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:quarkus" {...props}></Icon>
