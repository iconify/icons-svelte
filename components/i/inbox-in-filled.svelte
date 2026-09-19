<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg8uuk-ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yg8uuk-ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:inbox-in-filled" {...props}></Icon>
