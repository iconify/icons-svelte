<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xohei9bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xohei9bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:radio-sharp" {...props}></Icon>
