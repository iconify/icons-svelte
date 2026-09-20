<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6zd-wqxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v6zd-wqxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:asterisk-1-flat" {...props}></Icon>
