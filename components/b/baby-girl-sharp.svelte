<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1gh37bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1gh37bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:baby-girl-sharp" {...props}></Icon>
