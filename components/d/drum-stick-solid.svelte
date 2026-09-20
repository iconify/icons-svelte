<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlwccmptp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hlwccmptp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:drum-stick-solid" {...props}></Icon>
