<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etig-9n9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etig-9n9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-1-thin" {...props}></Icon>
