<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4hqp1bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4hqp1bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:brackets-curly" {...props}></Icon>
