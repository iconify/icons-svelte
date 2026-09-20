<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq4cvr6jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tq4cvr6jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:dumbbell" {...props}></Icon>
