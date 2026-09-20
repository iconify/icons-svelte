<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9nk7db_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9nk7db_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cat-filled" {...props}></Icon>
