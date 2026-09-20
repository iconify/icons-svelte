<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7kavkmvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7kavkmvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ins" {...props}></Icon>
