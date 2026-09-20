<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-cb7voab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-cb7voab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:gauge-sharp-fill" {...props}></Icon>
