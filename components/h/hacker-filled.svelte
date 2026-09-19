<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1kstfd5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1kstfd5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:hacker-filled" {...props}></Icon>
