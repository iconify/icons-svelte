<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdhts7ruk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdhts7ruk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pedastal-fan" {...props}></Icon>
