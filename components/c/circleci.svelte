<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlo59iqdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wlo59iqdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:circleci" {...props}></Icon>
