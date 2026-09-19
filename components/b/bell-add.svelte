<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8y7oacxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8y7oacxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bell-add" {...props}></Icon>
