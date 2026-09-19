<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo1nx8fzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zo1nx8fzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:customer-support-filled" {...props}></Icon>
