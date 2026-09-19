<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9-ahhtng.css';
import '../../css/j/jrhlkt36v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9-ahhtng"/><path clip-rule="evenodd" class="jrhlkt36v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:paper-bitcoin-filled" {...props}></Icon>
