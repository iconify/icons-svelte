<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayj-8mbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayj-8mbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-medium" {...props}></Icon>
