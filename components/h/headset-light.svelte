<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy3dqc0po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jy3dqc0po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:headset-light" {...props}></Icon>
