<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-06h4rzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-06h4rzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-pull-request" {...props}></Icon>
