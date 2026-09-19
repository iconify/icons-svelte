<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or6rs0b6f.css';
import '../../css/d/dqz2l5ijp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or6rs0b6f"/><path class="dqz2l5ijp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:notification-filled" {...props}></Icon>
