<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjqudmbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjqudmbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-dashed-minus-solid" {...props}></Icon>
