<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grekd176y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grekd176y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:conference-filled" {...props}></Icon>
