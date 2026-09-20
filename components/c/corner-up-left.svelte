<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-49-9v2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-49-9v2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-up-left" {...props}></Icon>
