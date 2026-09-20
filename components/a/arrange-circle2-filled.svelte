<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpol2ubiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpol2ubiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrange-circle2-filled" {...props}></Icon>
