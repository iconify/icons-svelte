<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpumycc1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qpumycc1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:briefcase4" {...props}></Icon>
