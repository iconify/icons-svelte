<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yov6v4b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yov6v4b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:curly-brackets-bold" {...props}></Icon>
