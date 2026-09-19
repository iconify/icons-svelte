<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or6rs0b6f.css';
import '../../css/z/z7sl-6blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="z7sl-6blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:notification-slash" {...props}></Icon>
