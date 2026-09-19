<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke1h4lbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke1h4lbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:insert-link" {...props}></Icon>
