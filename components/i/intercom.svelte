<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btp7u209s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btp7u209s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:intercom" {...props}></Icon>
