<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka9azccku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka9azccku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazonec2" {...props}></Icon>
