<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxqk6110f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxqk6110f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:magnifying-glass-plus" {...props}></Icon>
