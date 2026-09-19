<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqs2gk55e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oqs2gk55e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:dislike-fill" {...props}></Icon>
