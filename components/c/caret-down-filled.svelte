<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlcc6y7wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mlcc6y7wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:caret-down-filled" {...props}></Icon>
