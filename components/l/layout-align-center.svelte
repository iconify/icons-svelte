<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh8pccbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh8pccbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-align-center" {...props}></Icon>
