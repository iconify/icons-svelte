<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3qs-bclp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-1.5};
const content = `<path class="g3qs-bclp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:glue" {...props}></Icon>
