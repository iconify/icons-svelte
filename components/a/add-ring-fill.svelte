<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4iz5erop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4iz5erop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:add-ring-fill" {...props}></Icon>
