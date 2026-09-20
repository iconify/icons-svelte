<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho4qyubql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4qyubql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lumia" {...props}></Icon>
