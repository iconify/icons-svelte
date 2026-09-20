<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al31i_5jx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al31i_5jx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cloudcannon" {...props}></Icon>
