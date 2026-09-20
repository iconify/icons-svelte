<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz1oe71en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dz1oe71en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-caret-down-sharp-fill" {...props}></Icon>
