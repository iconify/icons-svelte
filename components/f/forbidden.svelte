<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwz2z7_7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lwz2z7_7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forbidden" {...props}></Icon>
