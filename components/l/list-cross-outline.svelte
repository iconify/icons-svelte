<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjvcbvbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjvcbvbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-cross-outline" {...props}></Icon>
