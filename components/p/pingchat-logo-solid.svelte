<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko7sfjdbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ko7sfjdbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:pingchat-logo-solid" {...props}></Icon>
