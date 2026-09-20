<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovd9g659q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovd9g659q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-align-top" {...props}></Icon>
