<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqg0evtvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqg0evtvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-forward-fill" {...props}></Icon>
