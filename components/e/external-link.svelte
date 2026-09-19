<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1-idtyoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1-idtyoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:external-link" {...props}></Icon>
