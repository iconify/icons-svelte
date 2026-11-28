<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-ublab8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-ublab8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:palette-edit" {...props}></Icon>
