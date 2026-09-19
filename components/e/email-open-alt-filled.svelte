<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2f2j9cea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2f2j9cea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-open-alt-filled" {...props}></Icon>
