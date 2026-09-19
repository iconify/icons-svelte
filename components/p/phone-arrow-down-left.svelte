<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se5c19beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se5c19beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:phone-arrow-down-left" {...props}></Icon>
