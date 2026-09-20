<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0d5y6b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h0d5y6b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-up-bold" {...props}></Icon>
