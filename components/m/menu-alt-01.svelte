<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scqqs5yey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="scqqs5yey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:menu-alt-01" {...props}></Icon>
