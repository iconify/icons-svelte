<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d64o0ob4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d64o0ob4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bell-alert" {...props}></Icon>
