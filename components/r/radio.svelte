<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjl7gynas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjl7gynas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:radio" {...props}></Icon>
