<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbw18bb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbw18bb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:relation-one-or-many-to-zero-or-one" {...props}></Icon>
