<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adk60db4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adk60db4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-4-sharp-fill" {...props}></Icon>
