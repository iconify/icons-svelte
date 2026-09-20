<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrju-_2fg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yrju-_2fg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:crown-sharp-fill" {...props}></Icon>
