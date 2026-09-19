<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/borxzzipv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="borxzzipv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-sm-down" {...props}></Icon>
