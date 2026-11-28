<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fn0n3pbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fn0n3pbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:number-6-solid" {...props}></Icon>
