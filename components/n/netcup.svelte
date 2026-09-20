<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgrr25wcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgrr25wcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:netcup" {...props}></Icon>
