<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzc8v-b8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzc8v-b8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:corner-left-down" {...props}></Icon>
