<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afqh7e3uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afqh7e3uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:glasses-line" {...props}></Icon>
