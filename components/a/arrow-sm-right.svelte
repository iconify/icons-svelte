<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx8n1l-fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx8n1l-fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-sm-right" {...props}></Icon>
