<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycz-ohbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ycz-ohbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-open-filled" {...props}></Icon>
