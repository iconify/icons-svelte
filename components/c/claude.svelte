<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvs6jjb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvs6jjb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:claude" {...props}></Icon>
