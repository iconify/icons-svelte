<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omllgdbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-2};
const content = `<path class="omllgdbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:redo" {...props}></Icon>
