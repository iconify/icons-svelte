<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5jk9l41j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c5jk9l41j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:carat" {...props}></Icon>
