<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4wi8qbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i4wi8qbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:layout-alt-02-filled" {...props}></Icon>
