<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9ycocbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b9ycocbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:incognito-filled" {...props}></Icon>
