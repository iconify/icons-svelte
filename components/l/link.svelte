<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozaq-2b7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozaq-2b7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:link" {...props}></Icon>
