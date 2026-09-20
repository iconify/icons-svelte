<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pog5twk5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pog5twk5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:add-square-fill" {...props}></Icon>
