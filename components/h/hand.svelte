<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uags2ccqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uags2ccqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:hand" {...props}></Icon>
