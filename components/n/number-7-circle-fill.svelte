<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wipuycb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wipuycb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-7-circle-fill" {...props}></Icon>
