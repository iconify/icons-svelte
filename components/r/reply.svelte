<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6d8yoboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6d8yoboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:reply" {...props}></Icon>
