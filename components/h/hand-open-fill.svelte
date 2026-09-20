<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpmfgxb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpmfgxb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hand-open-fill" {...props}></Icon>
