<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1j9ghh7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1j9ghh7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:option" {...props}></Icon>
