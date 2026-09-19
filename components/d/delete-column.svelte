<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj-zn2xho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-zn2xho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:delete-column" {...props}></Icon>
