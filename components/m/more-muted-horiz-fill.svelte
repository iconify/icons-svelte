<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsemppb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsemppb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-muted-horiz-fill" {...props}></Icon>
