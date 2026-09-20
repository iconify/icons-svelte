<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muv5wpe8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="muv5wpe8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-window-fill" {...props}></Icon>
