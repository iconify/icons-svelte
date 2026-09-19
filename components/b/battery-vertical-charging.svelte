<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq9c2zbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jq9c2zbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:battery-vertical-charging" {...props}></Icon>
