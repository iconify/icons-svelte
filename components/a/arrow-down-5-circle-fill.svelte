<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8p7wtb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8p7wtb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-down-5-circle-fill" {...props}></Icon>
