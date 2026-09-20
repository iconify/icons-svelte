<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/biljftzdn.css';
import '../../css/x/x56wbk0pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="biljftzdn"/><path clip-rule="evenodd" class="x56wbk0pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:burger" {...props}></Icon>
