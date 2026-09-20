<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw0g2wbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw0g2wbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:password-filled" {...props}></Icon>
