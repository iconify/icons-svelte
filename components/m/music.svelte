<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so3fk7beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="so3fk7beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:music" {...props}></Icon>
