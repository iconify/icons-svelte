<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbdh6-b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cbdh6-b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:npro" {...props}></Icon>
