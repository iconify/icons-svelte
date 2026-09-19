<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dizz0gbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dizz0gbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-dots-fill" {...props}></Icon>
